<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rquh9bckn.css';
import '../../css/z/zembkqbot.css';
import '../../css/o/ok1e7zbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rquh9bckn"/><path class="zembkqbot"/><path class="ok1e7zbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lighthouse-48-bold" /></template>
