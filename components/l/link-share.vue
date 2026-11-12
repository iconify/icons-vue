<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_kr5-bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_kr5-bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-share" /></template>
