<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txs0h11aa.css';
import '../../css/f/fgo78vant.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txs0h11aa"/><path clip-rule="evenodd" class="fgo78vant"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:earth-lock-filled" /></template>
