<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm7z1311u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm7z1311u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:imagetoolbox" /></template>
