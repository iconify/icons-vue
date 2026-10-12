<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2_e_29pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2_e_29pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hammer-filled" /></template>
