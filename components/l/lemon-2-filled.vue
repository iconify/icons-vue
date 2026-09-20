<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z486k_bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z486k_bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lemon-2-filled" /></template>
