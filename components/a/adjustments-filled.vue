<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epls_7bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epls_7bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-filled" /></template>
