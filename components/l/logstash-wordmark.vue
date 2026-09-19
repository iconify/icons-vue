<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5pdzmbry.css';
import '../../css/l/lm8lx4btl.css';
import '../../css/d/dvg27y9mf.css';
import '../../css/o/oi-s5cbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a5pdzmbry"/><path class="lm8lx4btl"/><path class="dvg27y9mf"/><path class="oi-s5cbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:logstash-wordmark" /></template>
