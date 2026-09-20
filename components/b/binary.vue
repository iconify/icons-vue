<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuum-zhnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuum-zhnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:binary" /></template>
