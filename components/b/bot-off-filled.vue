<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpriqvbir.css';
import '../../css/r/rosvxu7bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpriqvbir"/><path class="rosvxu7bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-off-filled" /></template>
