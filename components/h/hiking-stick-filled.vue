<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqiaa8e-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqiaa8e-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hiking-stick-filled" /></template>
