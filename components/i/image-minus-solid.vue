<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od1c0fb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od1c0fb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-minus-solid" /></template>
