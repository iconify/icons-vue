<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amf6pcb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amf6pcb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-drive-logo-2" /></template>
