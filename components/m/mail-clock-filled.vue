<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo3fevbda.css';
import '../../css/i/i-_k0ewmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wo3fevbda"/><path class="i-_k0ewmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-clock-filled" /></template>
