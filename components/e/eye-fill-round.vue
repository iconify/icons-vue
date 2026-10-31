<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nskupqbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nskupqbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-fill-round" /></template>
