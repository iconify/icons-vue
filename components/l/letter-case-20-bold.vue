<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6ofuubxb.css';
import '../../css/a/aw4zs_blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6ofuubxb"/><path class="aw4zs_blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-case-20-bold" /></template>
