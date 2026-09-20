<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpc_a-egz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpc_a-egz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-mysql" /></template>
