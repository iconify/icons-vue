<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx5cra-tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx5cra-tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-external-light" /></template>
