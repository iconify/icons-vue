<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imj4d0blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="imj4d0blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:instagram" /></template>
