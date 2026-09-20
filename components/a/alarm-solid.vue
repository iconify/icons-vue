<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1mfc1b6e.css';
import '../../css/m/m9-ge182a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e1mfc1b6e"/><path clip-rule="evenodd" class="m9-ge182a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:alarm-solid" /></template>
