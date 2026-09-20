<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llnax_bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="llnax_bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:alien-solid" /></template>
