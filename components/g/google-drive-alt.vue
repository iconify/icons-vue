<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id3e5ebcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id3e5ebcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:google-drive-alt" /></template>
