<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjoof61_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pjoof61_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-folder-remove-remove-minus-folder-subtract-delete" /></template>
