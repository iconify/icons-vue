<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yexrm9bgt.css';
import '../../css/b/bi3yz8b9a.css';
import '../../css/v/v964ge3ni.css';
import '../../css/h/htwye9bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yexrm9bgt"/><path class="bi3yz8b9a"/><path class="v964ge3ni"/><path class="htwye9bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corn-48-bold" /></template>
