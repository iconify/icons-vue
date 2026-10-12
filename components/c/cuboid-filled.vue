<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukd_6to3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukd_6to3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cuboid-filled" /></template>
