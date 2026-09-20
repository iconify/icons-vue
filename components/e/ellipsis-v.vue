<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kca43ld9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kca43ld9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:ellipsis-v" /></template>
