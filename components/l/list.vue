<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj46sjb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj46sjb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:list" /></template>
