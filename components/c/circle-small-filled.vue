<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd2v57b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pd2v57b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:circle-small-filled" /></template>
