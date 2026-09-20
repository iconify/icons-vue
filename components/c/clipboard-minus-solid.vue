<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ghkibrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="y_ghkibrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-minus-solid" /></template>
