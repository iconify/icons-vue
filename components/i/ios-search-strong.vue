<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/istshsb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="istshsb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-search-strong" /></template>
