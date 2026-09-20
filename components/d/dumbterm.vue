<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl0fpxpgn.css';
import '../../css/w/wci5zzb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="wl0fpxpgn"/><path class="wci5zzb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbterm" /></template>
