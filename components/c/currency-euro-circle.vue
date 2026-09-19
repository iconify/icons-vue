<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7l8-o35n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7l8-o35n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:currency-euro-circle" /></template>
