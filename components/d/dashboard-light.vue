<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze_7y96ni.css';
import '../../css/a/az8mb25cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_7y96ni"/><path class="az8mb25cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:dashboard-light" /></template>
