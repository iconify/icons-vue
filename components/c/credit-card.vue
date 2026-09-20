<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzjl_5b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pzjl_5b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:credit-card" /></template>
