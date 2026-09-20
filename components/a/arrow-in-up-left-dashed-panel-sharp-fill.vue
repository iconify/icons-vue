<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idq-hxb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idq-hxb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-up-left-dashed-panel-sharp-fill" /></template>
