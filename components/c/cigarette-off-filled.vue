<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6n1ambrh.css';
import '../../css/j/jcsy-xpip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6n1ambrh"/><path class="jcsy-xpip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cigarette-off-filled" /></template>
