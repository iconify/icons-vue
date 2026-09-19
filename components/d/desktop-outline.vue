<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv703tnxb.css';
import '../../css/o/o7jqpib-k.css';
import '../../css/o/oly_7o-mp.css';
import '../../css/p/pmq70fbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="vv703tnxb"/><path class="o7jqpib-k"/><path class="oly_7o-mp"/><path class="pmq70fbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:desktop-outline" /></template>
