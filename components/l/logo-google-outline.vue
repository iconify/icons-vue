<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgj4t2bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgj4t2bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-google-outline" /></template>
