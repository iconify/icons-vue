<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5vqzdoha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5vqzdoha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:homarr" /></template>
