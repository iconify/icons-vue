<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw4tq_q9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hw4tq_q9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dial-pad-finger-2-solid" /></template>
