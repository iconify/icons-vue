<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4w89svje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d4w89svje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:deezer" /></template>
