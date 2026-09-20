<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk0y0vb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk0y0vb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:blob" /></template>
