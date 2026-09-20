<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo0oht-lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo0oht-lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-horizontal" /></template>
