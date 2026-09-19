<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5x3eeo5d.css';
import '../../css/u/uuexlx2yt.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted o5x3eeo5d"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-2--alerted uuexlx2yt"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:block-solid-alerted" /></template>
