<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw2--ccna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw2--ccna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:earbuds-off-filled" /></template>
