<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwx9zx2bw.css';
import '../../css/o/ohisqfb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwx9zx2bw"/><path class="ohisqfb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-button-top-16" /></template>
