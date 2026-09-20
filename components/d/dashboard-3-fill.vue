<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjwvxny-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjwvxny-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-3-fill" /></template>
