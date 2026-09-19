<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1nlpp2od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="o1nlpp2od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:bullhorn" /></template>
