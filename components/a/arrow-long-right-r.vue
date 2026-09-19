<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjg90-bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wjg90-bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-right-r" /></template>
