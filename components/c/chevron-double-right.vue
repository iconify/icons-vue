<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of9-g8y0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of9-g8y0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chevron-double-right" /></template>
