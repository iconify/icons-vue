<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjyxfcb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjyxfcb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:download-filled" /></template>
