<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo960odbv.css';
import '../../css/t/tcdywobje.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo960odbv"/><path class="tcdywobje"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-key-filled" /></template>
