<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnljhyiuk.css';
import '../../css/w/wxymvdbcb.css';
import '../../css/e/eeqb4o0lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fnljhyiuk"/><path class="wxymvdbcb"/><path class="eeqb4o0lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fault-48" /></template>
