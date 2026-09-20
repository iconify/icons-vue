<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caf_-wbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="caf_-wbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horse" /></template>
