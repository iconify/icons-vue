<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9l6b08cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9l6b08cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camcorder" /></template>
