<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzf0gv1yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xzf0gv1yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hands-helping-solid" /></template>
