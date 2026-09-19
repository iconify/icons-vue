<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elbyz08-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="elbyz08-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-delete" /></template>
