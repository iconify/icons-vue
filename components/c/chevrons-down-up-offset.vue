<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymdmaybvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymdmaybvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-down-up-offset" /></template>
