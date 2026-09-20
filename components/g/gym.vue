<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxaj67-zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zxaj67-zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:gym" /></template>
