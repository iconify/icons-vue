<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz4fx2blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz4fx2blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:commit" /></template>
