<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow1xktbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="ow1xktbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:busket-ball" /></template>
