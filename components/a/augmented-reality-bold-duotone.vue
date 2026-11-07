<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg928d-qd.css';
import '../../css/a/a-44o5enj.css';
import '../../css/w/wn9x1iaaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path clip-rule="evenodd" class="a-44o5enj"/><path clip-rule="evenodd" class="wn9x1iaaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:augmented-reality-bold-duotone" /></template>
