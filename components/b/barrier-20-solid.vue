<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbflnobjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lbflnobjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:barrier-20-solid" /></template>
