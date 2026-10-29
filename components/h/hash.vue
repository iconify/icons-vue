<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zav3-ob_j.css';
import '../../css/m/m6r4ncclr.css';
import '../../css/u/ua1yalooh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zav3-ob_j"/><path class="m6r4ncclr wm-a"/><path class="ua1yalooh wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:hash" /></template>
