<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhqprgnjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhqprgnjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevrons-up-right-solid" /></template>
