<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsxw4ibir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsxw4ibir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:desk" /></template>
