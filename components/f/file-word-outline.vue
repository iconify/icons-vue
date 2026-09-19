<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq8y1_y2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq8y1_y2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-word-outline" /></template>
