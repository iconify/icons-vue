<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz6utjsfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz6utjsfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-minus-02" /></template>
