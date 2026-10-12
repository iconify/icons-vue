<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi3ptw9oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi3ptw9oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:columns-4-filled" /></template>
