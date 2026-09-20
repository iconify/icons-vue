<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfn47-bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfn47-bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-margin" /></template>
