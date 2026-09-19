<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g017-p78q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g017-p78q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:crown" /></template>
