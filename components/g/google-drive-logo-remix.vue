<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu14m29tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yu14m29tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:google-drive-logo-remix" /></template>
