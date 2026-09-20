<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfy8v3bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfy8v3bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grid-pattern" /></template>
