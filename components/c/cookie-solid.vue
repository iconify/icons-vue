<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsl4oblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clsl4oblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cookie-solid" /></template>
