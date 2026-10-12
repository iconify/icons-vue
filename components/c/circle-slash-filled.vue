<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqdvu0_5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqdvu0_5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-slash-filled" /></template>
