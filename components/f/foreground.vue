<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r90syqbvp.css';
import '../../css/j/jcmaqeb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r90syqbvp"/><path class="jcmaqeb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:foreground" /></template>
