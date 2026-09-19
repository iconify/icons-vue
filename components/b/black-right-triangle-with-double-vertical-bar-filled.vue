<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xow_l-_ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xow_l-_ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-right-triangle-with-double-vertical-bar-filled" /></template>
