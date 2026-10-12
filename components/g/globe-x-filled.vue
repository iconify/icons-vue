<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y82zzkv5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y82zzkv5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-x-filled" /></template>
