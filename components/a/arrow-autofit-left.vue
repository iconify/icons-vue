<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmjiwu9pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmjiwu9pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-left" /></template>
