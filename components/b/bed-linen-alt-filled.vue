<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm-mfbn3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nm-mfbn3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bed-linen-alt-filled" /></template>
