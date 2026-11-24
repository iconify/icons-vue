<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgsm_4xdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hgsm_4xdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:faucet-filled" /></template>
