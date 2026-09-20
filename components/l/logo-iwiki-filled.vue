<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fquq4wb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fquq4wb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-iwiki-filled" /></template>
