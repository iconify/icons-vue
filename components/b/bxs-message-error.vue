<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8myn--9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8myn--9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-error" /></template>
