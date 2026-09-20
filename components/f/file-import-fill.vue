<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gux4efbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gux4efbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-import-fill" /></template>
