<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-g5_2e4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-g5_2e4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-contact-outline" /></template>
