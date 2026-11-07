<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njk-keb-f.css';
import '../../css/e/e3g82dqvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njk-keb-f"/><path clip-rule="evenodd" class="e3g82dqvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:exit-outline" /></template>
