<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlj8xibzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlj8xibzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:clock-five" /></template>
