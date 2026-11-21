<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnc5a8hke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnc5a8hke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-remove-outline" /></template>
