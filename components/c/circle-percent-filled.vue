<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq9yxutpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq9yxutpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-percent-filled" /></template>
