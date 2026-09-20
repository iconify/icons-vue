<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b34_p4caa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b34_p4caa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:invite-line" /></template>
