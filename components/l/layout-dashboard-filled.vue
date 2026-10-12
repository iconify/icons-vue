<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv3vohdsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv3vohdsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-dashboard-filled" /></template>
