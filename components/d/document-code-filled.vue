<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omhq2obvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omhq2obvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document-code-filled" /></template>
