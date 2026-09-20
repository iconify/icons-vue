<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqgdw3bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqgdw3bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-medium-fill" /></template>
