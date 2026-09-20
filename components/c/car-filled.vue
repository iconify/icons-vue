<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkuxgfblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bkuxgfblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:car-filled" /></template>
