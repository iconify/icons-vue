<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_g9xobss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_g9xobss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:dices-f" /></template>
