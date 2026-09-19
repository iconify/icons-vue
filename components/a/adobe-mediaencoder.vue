<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aev39tqol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="aev39tqol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-mediaencoder" /></template>
