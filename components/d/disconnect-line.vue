<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmwgzixdw.css';
import '../../css/m/mgw07hszg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 vmwgzixdw"/><path class="clr-i-outline clr-i-outline-path-2 mgw07hszg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:disconnect-line" /></template>
