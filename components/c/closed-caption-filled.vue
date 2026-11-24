<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0k9p0bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0k9p0bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:closed-caption-filled" /></template>
