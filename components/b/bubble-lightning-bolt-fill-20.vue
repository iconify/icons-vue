<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi98z-bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pi98z-bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-lightning-bolt-fill-20" /></template>
