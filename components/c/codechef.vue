<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo2t9qb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo2t9qb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codechef" /></template>
