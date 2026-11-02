<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfquvubot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfquvubot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:down-small-line" /></template>
