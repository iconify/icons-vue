<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3qqrn2_d.css';
import '../../css/s/s7ccnp_vi.css';
import '../../css/r/rvkvl5b8b.css';
import '../../css/k/kvp5a_bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k3qqrn2_d"/><path class="s7ccnp_vi"/><path class="rvkvl5b8b"/><path class="kvp5a_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:floppydisk2" /></template>
