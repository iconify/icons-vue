<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szg_xwy0s.css';
import '../../css/e/eozjh4bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="szg_xwy0s"/><path class="eozjh4bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:list-clock-filled" /></template>
