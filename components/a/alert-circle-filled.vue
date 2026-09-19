<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atn4ffvgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atn4ffvgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:alert-circle-filled" /></template>
