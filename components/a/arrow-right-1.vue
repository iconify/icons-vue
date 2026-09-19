<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0nj7p_xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0nj7p_xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-1" /></template>
