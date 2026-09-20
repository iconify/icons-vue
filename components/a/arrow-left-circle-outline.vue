<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0n-9bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ak0n-9bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-left-circle-outline" /></template>
