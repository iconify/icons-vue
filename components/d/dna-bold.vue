<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okjza0b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="okjza0b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dna-bold" /></template>
