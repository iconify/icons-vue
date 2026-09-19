<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4_ippc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4_ippc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-sun" /></template>
