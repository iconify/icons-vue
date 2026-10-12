<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vczeidb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vczeidb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-pound-sterling-filled" /></template>
