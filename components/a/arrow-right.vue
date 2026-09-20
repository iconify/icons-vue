<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptjd14b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptjd14b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right" /></template>
