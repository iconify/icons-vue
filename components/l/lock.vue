<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty4pcbcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ty4pcbcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:lock" /></template>
