<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdqoy3z0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdqoy3z0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:at-filled" /></template>
