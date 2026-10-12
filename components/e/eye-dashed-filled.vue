<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j95p8463r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j95p8463r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:eye-dashed-filled" /></template>
