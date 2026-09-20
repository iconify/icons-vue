<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix285gbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix285gbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-open-check" /></template>
