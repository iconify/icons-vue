<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv8zs-_oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bv8zs-_oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:etsy" /></template>
