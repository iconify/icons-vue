<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb94g1vcp.css';
import '../../css/o/o5nyr_biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gb94g1vcp"/><path class="o5nyr_biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-platter-filled" /></template>
