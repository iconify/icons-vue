<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zotrfkt_o.css';
import '../../css/p/pec0a9bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zotrfkt_o"/><path clip-rule="evenodd" class="pec0a9bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-b-filled" /></template>
