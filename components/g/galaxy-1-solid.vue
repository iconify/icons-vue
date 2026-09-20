<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pykeo5baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pykeo5baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:galaxy-1-solid" /></template>
