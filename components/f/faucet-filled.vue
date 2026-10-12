<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y73pg9rpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y73pg9rpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:faucet-filled" /></template>
