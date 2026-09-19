<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd7leebis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd7leebis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:caret-forward-sharp" /></template>
