<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uagzrrb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uagzrrb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:abb" /></template>
