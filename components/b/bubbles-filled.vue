<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s176rmg_i.css';
import '../../css/r/rg-7atbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s176rmg_i"/><path class="rg-7atbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bubbles-filled" /></template>
