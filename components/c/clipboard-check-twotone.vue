<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaaj9w.css';
import '../../css/e/ei0d1h.css';
import '../../css/q/qa-o7h.css';
import '../../css/t/taf2xz.css';
import '../../css/f/f2o4kw.css';
import '../../css/z/zsjp5o.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaaj9w"/><path class="ei0d1h qa-o7h taf2xz"/><path class="f2o4kw qa-o7h"/><path class="qa-o7h taf2xz zsjp5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:clipboard-check-twotone" /></template>
