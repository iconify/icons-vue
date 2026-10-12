<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvihl5yzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvihl5yzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-chevron-up-filled" /></template>
