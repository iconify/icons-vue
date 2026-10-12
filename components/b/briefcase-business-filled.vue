<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvc5zobxq.css';
import '../../css/c/curqijbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvc5zobxq"/><path clip-rule="evenodd" class="curqijbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:briefcase-business-filled" /></template>
