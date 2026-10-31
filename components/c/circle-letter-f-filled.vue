<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oav7xsbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oav7xsbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-f-filled" /></template>
