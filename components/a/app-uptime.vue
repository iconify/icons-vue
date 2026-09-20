<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3symwlop.css';
import '../../css/y/ypo2h9ruk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k3symwlop ouiIcon__fillSecondary"/><path class="ypo2h9ruk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-uptime" /></template>
