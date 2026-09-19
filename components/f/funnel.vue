<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh_w36b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh_w36b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:funnel" /></template>
