<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfabtaczt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfabtaczt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-filled" /></template>
