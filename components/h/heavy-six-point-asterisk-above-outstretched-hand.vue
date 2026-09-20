<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocf6zpbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ocf6zpbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heavy-six-point-asterisk-above-outstretched-hand" /></template>
