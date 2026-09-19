<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfyn0ccck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mfyn0ccck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:blender-phone" /></template>
