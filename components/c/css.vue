<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-tbedc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-tbedc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:css" /></template>
