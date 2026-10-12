<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbn7xobus.css';
import '../../css/x/xz3gel1_a.css';
import '../../css/y/y4nt_6xmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xbn7xobus"/><path class="xz3gel1_a"/><path class="y4nt_6xmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flashlight-48-bold" /></template>
