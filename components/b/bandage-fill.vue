<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax9-xtuce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax9-xtuce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bandage-fill" /></template>
