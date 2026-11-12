<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkt-o0bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkt-o0bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-star" /></template>
