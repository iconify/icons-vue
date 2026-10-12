<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bixg4h3ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bixg4h3ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:laptop-filled" /></template>
