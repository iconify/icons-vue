<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yul2lzr6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yul2lzr6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-charging-02" /></template>
