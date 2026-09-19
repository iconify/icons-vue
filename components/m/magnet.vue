<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqrk28aif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqrk28aif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:magnet" /></template>
