<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eonvu3b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="eonvu3b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-folder-delete-remove-minus-folder-subtract-delete" /></template>
