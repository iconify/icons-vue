<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeiweu1nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xeiweu1nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ear-filled" /></template>
