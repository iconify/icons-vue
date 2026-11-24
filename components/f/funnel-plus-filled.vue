<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3e-_2bze.css';
import '../../css/n/n6-kt6b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3e-_2bze"/><path class="n6-kt6b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:funnel-plus-filled" /></template>
