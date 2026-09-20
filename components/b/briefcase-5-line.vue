<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsebfx-jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsebfx-jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:briefcase-5-line" /></template>
