<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1s00oj4b.css';
import '../../css/h/h4bvccbdl.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted v1s00oj4b"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted h4bvccbdl"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bank-solid-alerted" /></template>
