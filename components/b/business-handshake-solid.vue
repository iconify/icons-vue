<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sol4-bc4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sol4-bc4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:business-handshake-solid" /></template>
