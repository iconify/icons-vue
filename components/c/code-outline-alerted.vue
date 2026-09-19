<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c80hh1xpf.css';
import '../../css/n/nlux8tq9n.css';
import '../../css/h/hxlqp8bzq.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c80hh1xpf clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted nlux8tq9n"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted hxlqp8bzq"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:code-outline-alerted" /></template>
