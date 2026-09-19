<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz_4tkber.css';
import '../../css/q/q0dvizbgk.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted vz_4tkber"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-2--alerted q0dvizbgk"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:blocks-group-solid-alerted" /></template>
