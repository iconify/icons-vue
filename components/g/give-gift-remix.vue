<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5jeaofne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u5jeaofne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:give-gift-remix" /></template>
