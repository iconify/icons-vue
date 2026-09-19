<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crspx5bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":450,"height":512};
const content = `<path class="crspx5bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fontforge" /></template>
