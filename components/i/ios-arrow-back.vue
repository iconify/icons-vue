<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcb8w2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcb8w2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-back" /></template>
