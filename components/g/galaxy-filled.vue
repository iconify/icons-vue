<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzvlchb2u.css';
import '../../css/w/w1yuff-ay.css';
import '../../css/d/diidstw8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzvlchb2u"/><path clip-rule="evenodd" class="w1yuff-ay"/><path class="diidstw8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:galaxy-filled" /></template>
