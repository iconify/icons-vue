<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg1127bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg1127bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-knees-fill" /></template>
