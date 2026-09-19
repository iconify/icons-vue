<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz3gffb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zz3gffb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:align-center" /></template>
