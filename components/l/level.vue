<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkcoq_blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkcoq_blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:level" /></template>
