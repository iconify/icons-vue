<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y69hv9biv.css';
import '../../css/r/ro3kpsbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y69hv9biv"/><path class="ro3kpsbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:alert-24" /></template>
