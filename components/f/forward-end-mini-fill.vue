<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb-ppvbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb-ppvbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-end-mini-fill" /></template>
