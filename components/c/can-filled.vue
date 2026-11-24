<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_o1d_3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt_o1d_3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:can-filled" /></template>
