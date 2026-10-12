<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5eyj2bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5eyj2bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:between-vertical-start-filled" /></template>
