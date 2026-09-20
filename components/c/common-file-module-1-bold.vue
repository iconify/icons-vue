<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/altng4btx.css';
import '../../css/v/v7d9vybds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="altng4btx"/><path class="v7d9vybds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:common-file-module-1-bold" /></template>
