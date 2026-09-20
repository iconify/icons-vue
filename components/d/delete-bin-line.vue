<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyzslbc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyzslbc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:delete-bin-line" /></template>
