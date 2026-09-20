<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6k6h2o9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6k6h2o9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gameandwatch" /></template>
