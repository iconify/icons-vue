<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m40d-gbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m40d-gbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-ellipsis-filled" /></template>
