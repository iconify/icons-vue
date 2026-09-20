<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w91s3cc_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w91s3cc_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:6-minus" /></template>
