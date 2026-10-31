<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogigqt7lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogigqt7lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyboard-round" /></template>
