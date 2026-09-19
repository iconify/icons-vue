<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av-0g0bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av-0g0bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:external-link" /></template>
