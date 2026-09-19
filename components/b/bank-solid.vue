<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikua-wh6z.css';
import '../../css/v/v1s00oj4b.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ikua-wh6z"/><path class="clr-i-solid clr-i-solid-path-2 v1s00oj4b"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bank-solid" /></template>
