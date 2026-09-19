<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfoq6jk8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfoq6jk8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-round-forward" /></template>
