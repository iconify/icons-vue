<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3aun037f.css';
import '../../css/m/mt-ippa9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="e3aun037f"/><path clip-rule="evenodd" class="mt-ippa9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dollar-circle" /></template>
