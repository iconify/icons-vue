<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jatr1b-pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jatr1b-pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list-ordered" /></template>
