<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwlh1-3tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwlh1-3tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bed" /></template>
