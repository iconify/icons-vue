<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-q769oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-q769oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-audible" /></template>
