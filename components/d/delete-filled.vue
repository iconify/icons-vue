<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stf1opbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stf1opbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:delete-filled" /></template>
