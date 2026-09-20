<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcqmj_blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcqmj_blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-change-filled" /></template>
