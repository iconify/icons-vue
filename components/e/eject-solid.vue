<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckhw15x6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckhw15x6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:eject-solid" /></template>
