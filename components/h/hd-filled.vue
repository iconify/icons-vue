<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vszamwk3o.css';
import '../../css/t/twy8dkvem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vszamwk3o"/><path clip-rule="evenodd" class="twy8dkvem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hd-filled" /></template>
