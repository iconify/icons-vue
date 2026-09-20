<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmyb5bbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zmyb5bbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:controller-1-remix" /></template>
