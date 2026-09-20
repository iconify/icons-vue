<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/big0egopn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="big0egopn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-plus-outline" /></template>
