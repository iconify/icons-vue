<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7q6albzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c7q6albzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:closed-mailbox-lowered-flag" /></template>
