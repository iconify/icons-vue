<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7a0pibot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7a0pibot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:factory-02" /></template>
