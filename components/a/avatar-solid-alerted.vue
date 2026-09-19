<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6z_s2t8r.css';
import '../../css/o/or07ipb2g.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted l6z_s2t8r"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted or07ipb2g"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:avatar-solid-alerted" /></template>
