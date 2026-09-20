<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl1-0k6eb.css';
import '../../css/j/jj9_iwbid.css';
import '../../css/s/s9gd7lbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wl1-0k6eb"/><path class="jj9_iwbid"/><path class="s9gd7lbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glowstone" /></template>
