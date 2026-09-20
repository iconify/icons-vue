<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu58r9bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vu58r9bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hash" /></template>
