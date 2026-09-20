<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njun85gyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="njun85gyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:double-heart-solid" /></template>
