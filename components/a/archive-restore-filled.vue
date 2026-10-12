<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mijl2lbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mijl2lbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:archive-restore-filled" /></template>
