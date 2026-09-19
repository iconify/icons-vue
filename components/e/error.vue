<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7hgx0blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="z7hgx0blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:error" /></template>
