<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwirp0b1q.css';
import '../../css/e/efcc7ncew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwirp0b1q"/><path clip-rule="evenodd" class="efcc7ncew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-charge-outline" /></template>
