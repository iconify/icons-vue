<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in919sbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in919sbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-spreadsheet" /></template>
