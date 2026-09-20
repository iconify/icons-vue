<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj4jwx_5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xj4jwx_5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:drink" /></template>
