<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esid47bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esid47bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:diamond-plus-filled" /></template>
