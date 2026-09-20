<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2s5ybq2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2s5ybq2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layers-union" /></template>
