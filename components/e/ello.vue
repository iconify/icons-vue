<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8x-36bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="e8x-36bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:ello" /></template>
