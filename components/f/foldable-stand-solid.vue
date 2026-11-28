<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_samvsxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_samvsxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:foldable-stand-solid" /></template>
