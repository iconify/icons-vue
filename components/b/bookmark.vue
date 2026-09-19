<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q239t9bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="q239t9bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bookmark" /></template>
