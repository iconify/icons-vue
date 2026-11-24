<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deynqom5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deynqom5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chef-hat-filled" /></template>
