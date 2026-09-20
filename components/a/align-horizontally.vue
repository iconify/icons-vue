<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxm2gnbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxm2gnbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-horizontally" /></template>
