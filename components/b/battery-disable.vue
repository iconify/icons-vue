<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/her-4ob5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="her-4ob5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-disable" /></template>
