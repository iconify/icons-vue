<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p75bl6b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p75bl6b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:adobe" /></template>
