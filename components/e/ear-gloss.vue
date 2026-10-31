<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ps9nbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ps9nbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ear-gloss" /></template>
