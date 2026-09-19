<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb8hxx_up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zb8hxx_up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-text" /></template>
