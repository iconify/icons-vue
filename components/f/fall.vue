<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv9c24b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv9c24b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fall" /></template>
