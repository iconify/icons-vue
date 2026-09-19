<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p22yetmsi.css';
import '../../css/o/oe7n0nbcu.css';
import '../../css/d/dbknegbze.css';
import '../../css/x/xv7wunbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p22yetmsi"/><path class="oe7n0nbcu"/><path class="dbknegbze"/><path class="xv7wunbjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gamepad-duo" /></template>
