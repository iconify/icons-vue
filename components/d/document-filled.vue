<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj264cgmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vj264cgmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-filled" /></template>
