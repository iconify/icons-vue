<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc0h-ybnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc0h-ybnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-left-dash-filled" /></template>
