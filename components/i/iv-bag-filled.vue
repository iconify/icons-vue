<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oizfbkx3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oizfbkx3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:iv-bag-filled" /></template>
