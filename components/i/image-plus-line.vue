<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di5dbun5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di5dbun5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:image-plus-line" /></template>
