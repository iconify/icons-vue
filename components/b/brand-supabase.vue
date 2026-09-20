<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbu_b2b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbu_b2b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-supabase" /></template>
