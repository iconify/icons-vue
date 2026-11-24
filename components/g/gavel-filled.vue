<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmb5cnbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmb5cnbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gavel-filled" /></template>
