<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5-d9ibxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5-d9ibxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-top" /></template>
