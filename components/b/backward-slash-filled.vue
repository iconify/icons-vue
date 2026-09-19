<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpon2rbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpon2rbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:backward-slash-filled" /></template>
