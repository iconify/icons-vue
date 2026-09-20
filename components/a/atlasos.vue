<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fokc71-mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fokc71-mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:atlasos" /></template>
