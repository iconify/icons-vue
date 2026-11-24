<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-6jcabcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-6jcabcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-filled" /></template>
