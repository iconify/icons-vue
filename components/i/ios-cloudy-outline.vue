<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctjmp2b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ctjmp2b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloudy-outline" /></template>
