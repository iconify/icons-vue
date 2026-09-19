<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yze8n3h-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yze8n3h-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:alarm-clock-small-filled" /></template>
