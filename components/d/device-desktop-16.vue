<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaum-2bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aaum-2bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-desktop-16" /></template>
