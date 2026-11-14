<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/v550m8b4u.css';
import '../../css/s/saoofvbtd.css';
import '../../css/s/s00tgrb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="v550m8b4u"/><path class="saoofvbtd"/><path class="s00tgrb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:fuel-station-charging" /></template>
