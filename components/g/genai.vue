<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a025csbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path xmlns="http://www.w3.org/2000/svg" class="a025csbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:genai" /></template>
