<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5d8grbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5d8grbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:laptop-minimal-filled" /></template>
