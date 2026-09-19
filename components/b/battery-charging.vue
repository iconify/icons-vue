<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd1f270-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1f270-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:battery-charging" /></template>
