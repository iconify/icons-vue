<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taychab6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taychab6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-image-heart" /></template>
