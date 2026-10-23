<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqg1e6ggw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqg1e6ggw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bacon-filled" /></template>
