<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl9ykibaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl9ykibaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:charging-pile-fill" /></template>
