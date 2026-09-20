<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnq8zkb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnq8zkb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-right-circle" /></template>
