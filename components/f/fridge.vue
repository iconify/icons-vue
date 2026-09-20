<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr39v2-gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr39v2-gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fridge" /></template>
