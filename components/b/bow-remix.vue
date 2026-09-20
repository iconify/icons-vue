<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0i-87dsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m0i-87dsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bow-remix" /></template>
