<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phmuk5bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="phmuk5bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-picker-color-colors-design-dropper-eye-eyedrop-eyedropper-painting-picker" /></template>
