<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-qhpk12u.css';
import '../../css/k/kwhzwub2b.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 m-qhpk12u"/><path class="clr-i-solid clr-i-solid-path-2 kwhzwub2b"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:color-picker-solid" /></template>
