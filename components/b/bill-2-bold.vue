<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbslqbcic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbslqbcic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-2-bold" /></template>
