<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq26vi7tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq26vi7tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:haze-moon" /></template>
