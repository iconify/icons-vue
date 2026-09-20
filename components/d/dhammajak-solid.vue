<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irr05cczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="irr05cczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dhammajak-solid" /></template>
