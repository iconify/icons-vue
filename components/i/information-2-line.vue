<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfhr6oggz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfhr6oggz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:information-2-line" /></template>
