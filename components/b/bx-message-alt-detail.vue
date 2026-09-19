<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_30szf3s.css';
import '../../css/i/irjsvsbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_30szf3s"/><path class="irjsvsbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-alt-detail" /></template>
