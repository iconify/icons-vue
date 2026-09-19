<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qub73yblb.css';
import '../../css/j/jd-ahxb1j.css';
import '../../css/f/fk7qu-bqd.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qub73yblb"/><path class="clr-i-outline clr-i-outline-path-2 jd-ahxb1j"/><path class="clr-i-outline clr-i-outline-path-3 fk7qu-bqd"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:devices-line" /></template>
