<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vysuibbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vysuibbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:axis-x" /></template>
