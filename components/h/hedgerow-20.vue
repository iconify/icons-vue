<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3if92b-h.css';
import '../../css/l/l6eer9b_b.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3if92b-h"/><path class="l6eer9b_b"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hedgerow-20" /></template>
