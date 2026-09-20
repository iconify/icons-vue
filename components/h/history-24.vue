<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hohcf3gsm.css';
import '../../css/b/bmavll4ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hohcf3gsm"/><path class="bmavll4ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:history-24" /></template>
