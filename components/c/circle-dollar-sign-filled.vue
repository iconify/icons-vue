<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9eo20bcx.css';
import '../../css/p/p5f1kab4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9eo20bcx"/><path clip-rule="evenodd" class="p5f1kab4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-dollar-sign-filled" /></template>
