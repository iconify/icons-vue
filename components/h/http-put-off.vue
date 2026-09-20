<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf1ldn2li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1ldn2li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-put-off" /></template>
