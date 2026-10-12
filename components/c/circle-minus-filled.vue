<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hki5dibas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hki5dibas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-minus-filled" /></template>
