<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8by7gb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8by7gb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-settings" /></template>
