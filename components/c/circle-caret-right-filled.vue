<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si728y-uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si728y-uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-caret-right-filled" /></template>
