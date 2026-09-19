<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9rwhqbjf.css';
import '../../css/j/jlqtr1aep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9rwhqbjf"/><path class="jlqtr1aep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:biohazard" /></template>
