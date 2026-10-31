<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzfkap_kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzfkap_kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-ethereum-round" /></template>
