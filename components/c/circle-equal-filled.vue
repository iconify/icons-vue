<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmps9kb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmps9kb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-equal-filled" /></template>
