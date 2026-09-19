<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbjx-lv-q.css';
import '../../css/q/qlgirlt6q.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cbjx-lv-q clr-i-solid--alerted clr-i-solid-path-1--alerted"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted qlgirlt6q"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:file-settings-solid-alerted" /></template>
