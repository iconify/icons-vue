<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-9ypkn5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b-9ypkn5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:california" /></template>
