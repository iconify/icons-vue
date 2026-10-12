<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_txi0raq.css';
import '../../css/x/xb_-jcbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_txi0raq"/><path clip-rule="evenodd" class="xb_-jcbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:locate-fixed-filled" /></template>
