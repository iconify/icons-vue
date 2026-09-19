<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhpin-0sd.css';
import '../../css/y/y9o-uoblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhpin-0sd"/><path class="y9o-uoblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-woman" /></template>
