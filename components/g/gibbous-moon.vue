<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv02tvbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv02tvbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gibbous-moon" /></template>
