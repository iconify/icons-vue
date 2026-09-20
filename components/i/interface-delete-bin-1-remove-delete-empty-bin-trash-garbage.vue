<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iute2ob2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iute2ob2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-delete-bin-1-remove-delete-empty-bin-trash-garbage" /></template>
