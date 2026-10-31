<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j021hccwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j021hccwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-right-gloss" /></template>
