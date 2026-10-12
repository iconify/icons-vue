<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0y3lu1_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v0y3lu1_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-user-filled" /></template>
