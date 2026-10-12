<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbs36hbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbs36hbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gamepad-directional-filled" /></template>
