<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6b17ub6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6b17ub6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cuboid-filled" /></template>
