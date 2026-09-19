<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ixevwrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-ixevwrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-alert" /></template>
