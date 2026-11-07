<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-3ee_ik.css';
import '../../css/e/ecbj7fz0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh-3ee_ik"/><path class="ecbj7fz0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-top-down-bold" /></template>
