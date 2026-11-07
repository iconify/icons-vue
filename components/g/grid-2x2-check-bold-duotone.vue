<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5ogxjm1y.css';
import '../../css/o/o7wz-inek.css';
import '../../css/p/p8bolj64l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ogxjm1y"/><path class="o7wz-inek"/><path class="p8bolj64l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-check-bold-duotone" /></template>
