<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzo4to9sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzo4to9sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-plus-filled" /></template>
