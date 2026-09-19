<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6jy33b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6jy33b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-remove-circle" /></template>
