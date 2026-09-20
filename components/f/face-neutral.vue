<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqa_88bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqa_88bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-neutral" /></template>
