<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lydoh1n-z.css';
import '../../css/l/laty4l76k.css';
import '../../css/k/k_8z-tbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lydoh1n-z"/><path class="laty4l76k"/><path class="k_8z-tbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lasso-48-bold" /></template>
