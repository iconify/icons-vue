<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftc2pcbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ftc2pcbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-fn" /></template>
