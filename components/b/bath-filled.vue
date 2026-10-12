<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiw79xjwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiw79xjwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bath-filled" /></template>
