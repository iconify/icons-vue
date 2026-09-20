<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lca4iab0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lca4iab0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-case-upper" /></template>
