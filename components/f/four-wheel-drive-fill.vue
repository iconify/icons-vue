<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5vu71b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5vu71b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:four-wheel-drive-fill" /></template>
