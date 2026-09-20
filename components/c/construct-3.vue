<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1-mrcghs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1-mrcghs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:construct-3" /></template>
