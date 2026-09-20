<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf2pff15t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hf2pff15t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:application-add-solid" /></template>
