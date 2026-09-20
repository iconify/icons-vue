<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbn6v21yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbn6v21yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:assignment-return" /></template>
