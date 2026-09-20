<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prm7xpbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prm7xpbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:filter-remove-24" /></template>
