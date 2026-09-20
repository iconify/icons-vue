<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5wwqfbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5wwqfbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-box-line" /></template>
