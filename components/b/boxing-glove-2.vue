<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlnerbb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlnerbb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:boxing-glove-2" /></template>
