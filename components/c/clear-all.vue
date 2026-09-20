<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stjn2_b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stjn2_b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clear-all" /></template>
