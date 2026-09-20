<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp5g3kjqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp5g3kjqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-box-outline" /></template>
