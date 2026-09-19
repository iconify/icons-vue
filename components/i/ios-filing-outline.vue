<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cay9onbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cay9onbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-filing-outline" /></template>
