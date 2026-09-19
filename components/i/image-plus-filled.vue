<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf_ej1bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hf_ej1bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-plus-filled" /></template>
