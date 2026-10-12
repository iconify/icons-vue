<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyue1vbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyue1vbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gem-filled" /></template>
