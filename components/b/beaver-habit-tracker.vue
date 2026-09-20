<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_fc_bb1g.css';
import '../../css/m/mo96-mi7j.css';
import '../../css/a/as7o-d6nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_fc_bb1g"/><path class="mo96-mi7j"/><path class="as7o-d6nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beaver-habit-tracker" /></template>
