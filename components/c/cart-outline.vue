<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3apaccql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s3apaccql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cart-outline" /></template>
