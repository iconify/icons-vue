<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm572wv6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hm572wv6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:chsb" /></template>
