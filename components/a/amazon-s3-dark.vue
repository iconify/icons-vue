<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpw_gduhr.css';
import '../../css/m/m-hjm3bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpw_gduhr"/><path class="m-hjm3bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-s3-dark" /></template>
