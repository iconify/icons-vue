<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcu-63jaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcu-63jaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:edit-document-filled" /></template>
