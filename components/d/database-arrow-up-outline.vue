<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3yy7pbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3yy7pbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-arrow-up-outline" /></template>
