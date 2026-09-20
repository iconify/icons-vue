<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0np1_b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0np1_b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:astral" /></template>
