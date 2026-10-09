<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shss9gboo.css';
import '../../css/w/wik2ozbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="shss9gboo"/><path class="wik2ozbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-down-20" /></template>
