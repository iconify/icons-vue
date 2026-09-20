<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guf9n9spv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guf9n9spv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-mosque" /></template>
