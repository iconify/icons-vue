<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku9hb1yoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku9hb1yoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-charging-filled" /></template>
