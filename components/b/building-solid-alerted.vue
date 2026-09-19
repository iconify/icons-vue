<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck7afkfhj.css';
import '../../css/c/cbrcji36c.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ck7afkfhj clr-i-solid--alerted clr-i-solid-path-1--alerted"/><path class="cbrcji36c clr-i-solid--alerted clr-i-solid-path-2--alerted"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:building-solid-alerted" /></template>
