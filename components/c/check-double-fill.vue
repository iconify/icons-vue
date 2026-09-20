<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cukkrffgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cukkrffgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:check-double-fill" /></template>
