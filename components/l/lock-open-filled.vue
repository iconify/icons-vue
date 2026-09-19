<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aimve_b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aimve_b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-open-filled" /></template>
