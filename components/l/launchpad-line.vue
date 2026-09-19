<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fikfu_54f.css';
import '../../css/e/ec43nwb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fikfu_54f"/><path class="ec43nwb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:launchpad-line" /></template>
