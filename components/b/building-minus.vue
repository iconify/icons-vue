<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znx86gb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znx86gb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-minus" /></template>
