<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2ip-cb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j2ip-cb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:fan" /></template>
