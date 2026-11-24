<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwieclb2b.css';
import '../../css/i/i26zuu1we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwieclb2b"/><path class="i26zuu1we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:beer-off-filled" /></template>
