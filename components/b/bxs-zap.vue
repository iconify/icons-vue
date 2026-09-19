<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irsmad-tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irsmad-tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-zap" /></template>
