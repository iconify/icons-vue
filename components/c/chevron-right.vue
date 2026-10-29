<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8w0ypeiq.css';
import '../../css/n/nox4hglku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8w0ypeiq"/><path class="nox4hglku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chevron-right" /></template>
