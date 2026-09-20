<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6j7f0r3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6j7f0r3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bug-remix" /></template>
