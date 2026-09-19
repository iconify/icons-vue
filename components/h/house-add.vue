<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rngyk4bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rngyk4bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:house-add" /></template>
