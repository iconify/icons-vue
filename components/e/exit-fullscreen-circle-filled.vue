<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz2z0-b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz2z0-b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:exit-fullscreen-circle-filled" /></template>
