<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-sigjbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v-sigjbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:checkmark-circled-filled" /></template>
