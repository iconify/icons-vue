<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/web3leb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="web3leb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-square-for-stop-filled" /></template>
