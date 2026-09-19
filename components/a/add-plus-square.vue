<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df8xwmbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df8xwmbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:add-plus-square" /></template>
