<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvc9jbl1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nvc9jbl1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campfire-in-arch" /></template>
