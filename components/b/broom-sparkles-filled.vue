<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb7tk6biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb7tk6biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:broom-sparkles-filled" /></template>
