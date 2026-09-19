<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iddxurbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iddxurbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-unlock" /></template>
