<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eddf4cbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eddf4cbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:file-content-filled" /></template>
