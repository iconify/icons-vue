<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egbfch_mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egbfch_mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lasso-filled" /></template>
