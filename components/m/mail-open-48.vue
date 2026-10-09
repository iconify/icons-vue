<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_8ipno6c.css';
import '../../css/i/iaquidtow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_8ipno6c"/><path class="iaquidtow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-open-48" /></template>
