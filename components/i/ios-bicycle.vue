<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv9o7hb4h.css';
import '../../css/b/bpl-meb0s.css';
import '../../css/i/ic--wlbit.css';
import '../../css/p/pmf4o37fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bv9o7hb4h"/><path class="bpl-meb0s"/><path class="ic--wlbit"/><path class="pmf4o37fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bicycle" /></template>
