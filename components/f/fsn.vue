<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp1i4ac4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp1i4ac4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fsn" /></template>
