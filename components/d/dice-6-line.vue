<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajarnlbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajarnlbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-6-line" /></template>
