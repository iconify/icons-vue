<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1-oiviax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1-oiviax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:help-circle-filled" /></template>
