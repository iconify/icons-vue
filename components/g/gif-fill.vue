<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz64ambus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz64ambus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:gif-fill" /></template>
