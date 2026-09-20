<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-98sbyh.css';
import '../../css/k/kpvxz2bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-98sbyh"/><path class="kpvxz2bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:door-open" /></template>
