<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc0nuhbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cc0nuhbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:data-transfer-sync" /></template>
