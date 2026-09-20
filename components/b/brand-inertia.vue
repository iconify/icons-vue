<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6eqh_5vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6eqh_5vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-inertia" /></template>
