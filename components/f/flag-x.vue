<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8kur5tgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8kur5tgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-x" /></template>
