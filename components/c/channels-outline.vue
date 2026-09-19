<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t837arbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t837arbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:channels-outline" /></template>
