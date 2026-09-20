<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_jc_-b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d_jc_-b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:elbow" /></template>
