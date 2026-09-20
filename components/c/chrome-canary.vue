<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd6mj9e-i.css';
import '../../css/d/dn5b1_f-b.css';
import '../../css/p/phprfuhss.css';
import '../../css/p/p6_7y-bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vd6mj9e-i"/><circle class="dn5b1_f-b"/><path class="phprfuhss"/><path class="p6_7y-bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chrome-canary" /></template>
