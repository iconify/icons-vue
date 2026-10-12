<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dboz0cbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dboz0cbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fence-filled" /></template>
