<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjyisn2gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjyisn2gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-2x2-x-solid" /></template>
