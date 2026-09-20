<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te44gg.css';
import '../../css/b/bnsnku.css';
import '../../css/q/qa-o7h.css';
import '../../css/f/f2o4kw.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te44gg"/><path class="bnsnku qa-o7h"/><path class="f2o4kw qa-o7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:clipboard-twotone" /></template>
