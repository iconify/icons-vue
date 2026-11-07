<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us4-9fqqe.css';
import '../../css/o/o1z7omb5q.css';
import '../../css/f/fo4-y40vu.css';
import '../../css/s/sg53hmyvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us4-9fqqe"/><path class="o1z7omb5q"/><path class="fo4-y40vu"/><path class="sg53hmyvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:container-outline" /></template>
