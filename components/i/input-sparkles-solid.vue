<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foh-cvbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foh-cvbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-sparkles-solid" /></template>
