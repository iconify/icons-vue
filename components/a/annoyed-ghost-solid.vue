<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgy5n6fkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgy5n6fkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:annoyed-ghost-solid" /></template>
