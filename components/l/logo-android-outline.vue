<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-0a6u8qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-0a6u8qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-android-outline" /></template>
