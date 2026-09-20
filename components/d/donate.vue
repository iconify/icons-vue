<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_p301b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w_p301b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:donate" /></template>
