<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jka51-nhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jka51-nhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-medical-outline" /></template>
