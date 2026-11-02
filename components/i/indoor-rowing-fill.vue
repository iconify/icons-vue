<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xumdxw0gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xumdxw0gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:indoor-rowing-fill" /></template>
