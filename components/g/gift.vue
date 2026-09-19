<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjdqufb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xjdqufb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:gift" /></template>
