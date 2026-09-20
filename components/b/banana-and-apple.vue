<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht-nwvn7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ht-nwvn7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banana-and-apple" /></template>
