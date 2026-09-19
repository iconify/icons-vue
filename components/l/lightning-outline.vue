<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lchqymb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lchqymb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:lightning-outline" /></template>
