<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-imqxbqc.css';
import '../../css/i/i6ih-jbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-imqxbqc"/><path class="i6ih-jbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-conditioning-48-bold" /></template>
