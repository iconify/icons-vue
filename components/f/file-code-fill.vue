<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iss_gdbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iss_gdbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-code-fill" /></template>
