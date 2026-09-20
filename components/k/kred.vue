<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv6mthbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv6mthbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kred" /></template>
