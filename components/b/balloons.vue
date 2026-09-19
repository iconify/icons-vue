<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt7lupb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt7lupb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:balloons" /></template>
