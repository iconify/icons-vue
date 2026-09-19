<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf6nftywu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1760,"height":1792};
const content = `<path class="mf6nftywu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:google-wallet" /></template>
