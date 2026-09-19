<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jayb1w7jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jayb1w7jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-square" /></template>
