<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjslyj_rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjslyj_rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:audio-lines-off" /></template>
