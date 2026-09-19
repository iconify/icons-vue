<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1uvyt01z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="x1uvyt01z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:box-open" /></template>
