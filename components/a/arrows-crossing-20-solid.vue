<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd70iymwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qd70iymwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrows-crossing-20-solid" /></template>
