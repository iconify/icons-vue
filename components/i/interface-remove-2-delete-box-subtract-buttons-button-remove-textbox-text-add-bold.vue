<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuik6ebaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<rect class="iuik6ebaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-remove-2-delete-box-subtract-buttons-button-remove-textbox-text-add-bold" /></template>
