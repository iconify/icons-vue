<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrtf6oooz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrtf6oooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:library-solid" /></template>
