<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtyipexp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjtyipexp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-apple-appstore" /></template>
