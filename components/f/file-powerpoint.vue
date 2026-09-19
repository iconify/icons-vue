<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd6labbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="rd6labbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:file-powerpoint" /></template>
