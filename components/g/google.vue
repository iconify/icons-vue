<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1tlgu4fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="z1tlgu4fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:google" /></template>
