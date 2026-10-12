<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc1up6d3b.css';
import '../../css/r/rpiivsbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc1up6d3b"/><path class="rpiivsbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-pen-filled" /></template>
