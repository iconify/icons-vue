<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alk5rr8yk.css';
import '../../css/p/pwnej6bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="alk5rr8yk"/><path class="pwnej6bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:icicles-48-bold" /></template>
