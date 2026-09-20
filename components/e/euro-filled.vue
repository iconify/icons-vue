<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbdc2tb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbdc2tb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:euro-filled" /></template>
