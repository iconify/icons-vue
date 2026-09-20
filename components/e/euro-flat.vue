<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo7lvo_4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fo7lvo_4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:euro-flat" /></template>
