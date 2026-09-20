<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsh1b3tio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tsh1b3tio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-1-fill" /></template>
