<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbj99fbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbj99fbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:luggage-filled" /></template>
