<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5j_i5b7x.css';
import '../../css/m/m-hjm3bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5j_i5b7x"/><path class="m-hjm3bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-s3-dark" /></template>
