<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h194vi7el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h194vi7el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-three" /></template>
