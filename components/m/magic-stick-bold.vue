<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxk_x0b5m.css';
import '../../css/i/i5wfaac8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxk_x0b5m"/><path class="i5wfaac8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magic-stick-bold" /></template>
