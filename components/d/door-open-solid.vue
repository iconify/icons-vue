<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd6dxr9fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd6dxr9fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:door-open-solid" /></template>
