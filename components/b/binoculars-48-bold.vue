<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1wytabzg.css';
import '../../css/n/n65fkti1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a1wytabzg"/><path class="n65fkti1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binoculars-48-bold" /></template>
