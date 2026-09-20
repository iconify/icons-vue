<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlp_1cbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qlp_1cbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:instagram-outline" /></template>
