<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyroutbbi.css';
import '../../css/d/dgmtc731l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vyroutbbi"/><circle class="dgmtc731l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikimedia-commons" /></template>
