<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk4n348sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hk4n348sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:aws" /></template>
