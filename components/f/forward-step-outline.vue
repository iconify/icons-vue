<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjgk_8pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgjgk_8pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:forward-step-outline" /></template>
