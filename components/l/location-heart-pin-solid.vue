<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4oc5bcrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z4oc5bcrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:location-heart-pin-solid" /></template>
