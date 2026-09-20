<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jptnn3ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jptnn3ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-record-3-solid" /></template>
