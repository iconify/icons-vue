<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v__ot5lqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v__ot5lqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:castle-fill" /></template>
