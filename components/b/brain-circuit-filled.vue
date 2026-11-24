<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw8a2j_zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8a2j_zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brain-circuit-filled" /></template>
