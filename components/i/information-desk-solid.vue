<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt4tabrjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pt4tabrjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:information-desk-solid" /></template>
