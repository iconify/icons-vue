<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br25d5blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br25d5blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cone-plus" /></template>
