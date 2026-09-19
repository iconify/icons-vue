<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncda9abqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ncda9abqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:key" /></template>
