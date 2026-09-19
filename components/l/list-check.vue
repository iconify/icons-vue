<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkicm5bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkicm5bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:list-check" /></template>
