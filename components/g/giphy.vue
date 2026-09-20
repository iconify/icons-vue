<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz4mkebaq.css';
import '../../css/y/ylzf4_8rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz4mkebaq"/><path class="ylzf4_8rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:giphy" /></template>
