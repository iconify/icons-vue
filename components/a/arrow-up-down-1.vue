<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds6f2iupw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds6f2iupw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-up-down-1" /></template>
