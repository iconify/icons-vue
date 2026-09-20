<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy4cpbyhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cy4cpbyhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:headset-outline" /></template>
