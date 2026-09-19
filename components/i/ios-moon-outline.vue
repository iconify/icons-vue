<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bodb8dxau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bodb8dxau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-moon-outline" /></template>
