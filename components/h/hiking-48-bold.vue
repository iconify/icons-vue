<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-w-lr1f.css';
import '../../css/d/db7c96bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bi-w-lr1f"/><path class="db7c96bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hiking-48-bold" /></template>
