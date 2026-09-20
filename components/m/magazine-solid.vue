<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev6bxmbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ev6bxmbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:magazine-solid" /></template>
