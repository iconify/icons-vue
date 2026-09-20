<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw6l7tbdq.css';
import '../../css/d/dzjiyss3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fw6l7tbdq"/><path class="dzjiyss3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:golf-cart" /></template>
