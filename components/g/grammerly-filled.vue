<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqn-dor0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqn-dor0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grammerly-filled" /></template>
