<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrsb5o73i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrsb5o73i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-diff-filled" /></template>
