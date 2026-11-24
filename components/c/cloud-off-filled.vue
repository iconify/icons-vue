<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs_74ac8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs_74ac8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-off-filled" /></template>
