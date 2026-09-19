<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxwvkfgrp.css';
import '../../css/p/px1zdkb_w.css';
import '../../css/j/j37p75d_u.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted cxwvkfgrp"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted px1zdkb_w"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted j37p75d_u"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:file-settings-outline-alerted" /></template>
