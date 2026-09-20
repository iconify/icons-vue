<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh_9q-5fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_9q-5fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle" /></template>
