<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7_mocrpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7_mocrpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:flag-24" /></template>
