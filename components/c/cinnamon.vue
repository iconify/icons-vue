<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_o1j080n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":727};
const content = `<path class="s_o1j080n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:cinnamon" /></template>
