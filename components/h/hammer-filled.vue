<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek9xd-8cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ek9xd-8cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hammer-filled" /></template>
