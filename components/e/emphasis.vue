<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnxltmhny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnxltmhny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emphasis" /></template>
