<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b55fsm9et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b55fsm9et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cool-box-filled" /></template>
