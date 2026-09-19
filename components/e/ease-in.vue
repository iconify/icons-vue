<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txpoe7bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txpoe7bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ease-in" /></template>
