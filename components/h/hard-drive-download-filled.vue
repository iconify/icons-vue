<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg_u039uv.css';
import '../../css/e/e0kfvbb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg_u039uv"/><path class="e0kfvbb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hard-drive-download-filled" /></template>
