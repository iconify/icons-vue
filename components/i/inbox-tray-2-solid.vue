<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkrahr8qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dkrahr8qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-tray-2-solid" /></template>
