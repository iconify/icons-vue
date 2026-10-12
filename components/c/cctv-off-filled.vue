<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_nt-ijv.css';
import '../../css/n/nwez_dbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in_nt-ijv"/><path class="nwez_dbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cctv-off-filled" /></template>
