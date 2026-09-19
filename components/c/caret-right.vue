<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpn-mxb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bpn-mxb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:caret-right" /></template>
