<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7alv7cdp.css';
import '../../css/n/nwqnbxblf.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<rect class="clr-i-outline--alerted clr-i-outline-path-1--alerted g7alv7cdp" transform="rotate(-45 11.192 12.004)"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted nwqnbxblf"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:key-outline-alerted" /></template>
