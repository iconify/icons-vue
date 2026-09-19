<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so7h_yp_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so7h_yp_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-narrow-right" /></template>
