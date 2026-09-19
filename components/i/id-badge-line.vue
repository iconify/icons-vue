<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg3jy0b5j.css';
import '../../css/y/y23fb-bou.css';
import '../../css/s/sn4y9wbhh.css';
import '../../css/d/dhuoqxbpk.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 fg3jy0b5j"/><path class="clr-i-outline clr-i-outline-path-2 y23fb-bou"/><path class="clr-i-outline clr-i-outline-path-3 sn4y9wbhh"/><path class="clr-i-outline clr-i-outline-path-4 dhuoqxbpk"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:id-badge-line" /></template>
