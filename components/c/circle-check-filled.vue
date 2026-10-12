<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mulb_7wla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mulb_7wla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-check-filled" /></template>
