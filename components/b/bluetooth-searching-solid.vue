<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v11pwac-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v11pwac-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bluetooth-searching-solid" /></template>
