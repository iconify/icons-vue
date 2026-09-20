<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6_dgeb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6_dgeb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-lyd" /></template>
