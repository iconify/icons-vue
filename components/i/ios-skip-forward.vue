<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igi_seb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igi_seb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-skip-forward" /></template>
