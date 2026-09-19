<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7f1au4gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q7f1au4gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:closed-mailbox-raised-flag" /></template>
