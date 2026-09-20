<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krf3bhb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krf3bhb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-top" /></template>
