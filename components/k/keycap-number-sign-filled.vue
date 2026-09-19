<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndu34km1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ndu34km1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-number-sign-filled" /></template>
