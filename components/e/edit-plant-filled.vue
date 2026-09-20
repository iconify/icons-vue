<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxkl48b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fxkl48b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:edit-plant-filled" /></template>
