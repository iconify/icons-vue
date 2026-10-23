<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llxc-801q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llxc-801q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-chevrons-down-filled" /></template>
