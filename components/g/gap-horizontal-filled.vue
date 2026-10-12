<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw4sjwb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw4sjwb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gap-horizontal-filled" /></template>
