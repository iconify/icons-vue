<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbx04m8qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbx04m8qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lock-keyhole-open-filled" /></template>
