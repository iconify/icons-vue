<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptypnvblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ptypnvblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:image-photo-compsition-horizontal-camera-horizontal-panorama-composition-photography-photo-pictures" /></template>
