<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-qd2pbhi.css';
import '../../css/h/h2t_13bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-qd2pbhi"/><path clip-rule="evenodd" class="h2t_13bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:heart-plus-outline" /></template>
