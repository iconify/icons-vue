<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk_8nrbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rk_8nrbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-slash-20-solid" /></template>
