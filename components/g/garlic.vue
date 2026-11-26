<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/g/g3pqeb8sc.css';
import '../../css/q/qhpxm1b8e.css';
import '../../css/s/sl3savbof.css';
import '../../css/g/gk4a95bby.css';
import '../../css/f/fwrb9tb-m.css';
import '../../css/v/vtw3x8bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGlpSODbob" cx="74.8" cy="68.8" r="144" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".85" class="g3pqeb8sc"/><stop offset="1" class="g3pqeb8sc"/></radialGradient></defs><path class="qhpxm1b8e"/><path fill="url(#SVGlpSODbob)" transform="matrix(2.5 0 0 2.5 9.6 -3.78)" class="sl3savbof"/><path class="gk4a95bby"/><path class="fwrb9tb-m"/><path class="vtw3x8bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:garlic" /></template>
