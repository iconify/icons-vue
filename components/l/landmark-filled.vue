<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7-n71b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7-n71b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:landmark-filled" /></template>
