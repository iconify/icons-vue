<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e20bdlhct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e20bdlhct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:file-filled" /></template>
