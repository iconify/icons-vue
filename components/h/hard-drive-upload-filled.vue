<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg_u039uv.css';
import '../../css/e/e2m_lkbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg_u039uv"/><path class="e2m_lkbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hard-drive-upload-filled" /></template>
