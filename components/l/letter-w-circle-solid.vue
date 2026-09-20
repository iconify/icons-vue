<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw7-8ydfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw7-8ydfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-w-circle-solid" /></template>
