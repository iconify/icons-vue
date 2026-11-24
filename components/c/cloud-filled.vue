<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-w1q-0ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-w1q-0ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-filled" /></template>
