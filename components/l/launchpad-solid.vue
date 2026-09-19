<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_kc2bft.css';
import '../../css/q/qxu9d8l6m.css';
import '../../css/t/thy0iw71r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n1_kc2bft"/><path class="qxu9d8l6m"/><path class="thy0iw71r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:launchpad-solid" /></template>
