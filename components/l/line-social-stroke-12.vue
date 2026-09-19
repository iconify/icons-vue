<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur7a1h35t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ur7a1h35t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:line-social-stroke-12" /></template>
