<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guro_cc7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="guro_cc7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:closet-solid" /></template>
