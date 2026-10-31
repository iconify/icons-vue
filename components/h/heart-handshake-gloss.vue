<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar4x5b1ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar4x5b1ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-handshake-gloss" /></template>
