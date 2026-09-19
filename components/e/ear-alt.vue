<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slwo16b5l.css';
import '../../css/u/uv22sacky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slwo16b5l"/><path class="uv22sacky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ear-alt" /></template>
