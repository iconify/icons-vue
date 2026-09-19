<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxft3ybyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sxft3ybyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-tools" /></template>
