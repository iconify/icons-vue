<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-8tu9-dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-8tu9-dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-diagonal-minimize-2" /></template>
