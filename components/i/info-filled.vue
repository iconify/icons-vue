<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/telbe8qah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="telbe8qah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:info-filled" /></template>
