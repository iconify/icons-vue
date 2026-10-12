<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8zqi2t4s.css';
import '../../css/x/x44at5b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8zqi2t4s"/><path clip-rule="evenodd" class="x44at5b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ham-filled" /></template>
