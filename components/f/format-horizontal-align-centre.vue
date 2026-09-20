<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6n6gll-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6n6gll-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-horizontal-align-centre" /></template>
