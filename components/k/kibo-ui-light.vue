<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uniwpj3nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":117,"height":116};
const content = `<path clip-rule="evenodd" class="uniwpj3nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kibo-ui-light" /></template>
