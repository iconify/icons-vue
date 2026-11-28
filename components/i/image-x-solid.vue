<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/begruvb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="begruvb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-x-solid" /></template>
