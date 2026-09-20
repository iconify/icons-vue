<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw_83acpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw_83acpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:add-friends-filled" /></template>
