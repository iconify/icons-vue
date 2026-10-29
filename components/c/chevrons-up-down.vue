<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klgbgacfz.css';
import '../../css/i/iqri69b9x.css';
import '../../css/e/eym2zmgyf.css';
import '../../css/z/zq95thb2u.css';
import '../../css/r/rx-8bii_n.css';
import '../../css/p/pgac3b_fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klgbgacfz wm-shadow"/><path class="iqri69b9x wm-k"/><path class="eym2zmgyf wm-k"/><path class="wm-k zq95thb2u"/><path class="rx-8bii_n wm-k"/><path class="pgac3b_fi wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chevrons-up-down" /></template>
