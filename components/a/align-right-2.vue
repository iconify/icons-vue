<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcc8neiip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcc8neiip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-right-2" /></template>
