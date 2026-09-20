<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eurm6x-rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eurm6x-rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:artboard-off" /></template>
