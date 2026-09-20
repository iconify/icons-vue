<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyyvso_mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eyyvso_mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-incoming-solid" /></template>
