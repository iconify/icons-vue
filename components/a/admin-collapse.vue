<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbs-mwb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zbs-mwb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-collapse" /></template>
