<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo5-0ek9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo5-0ek9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-threads" /></template>
