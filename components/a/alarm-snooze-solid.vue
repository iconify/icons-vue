<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdp6nbcid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdp6nbcid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-snooze-solid" /></template>
