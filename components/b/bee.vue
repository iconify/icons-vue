<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9n4vlb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i9n4vlb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bee" /></template>
