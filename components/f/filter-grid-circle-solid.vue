<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5rcylbor.css';
import '../../css/o/oxmfj5ier.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 l5rcylbor"/><path class="clr-i-solid clr-i-solid-path-2 oxmfj5ier"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:filter-grid-circle-solid" /></template>
