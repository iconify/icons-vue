<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hql3ldhxa.css';
import '../../css/o/oynu9y2bq.css';
import '../../css/c/cxlln6pqv.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 hql3ldhxa"/><path class="clr-i-solid clr-i-solid-path-2 oynu9y2bq"/><path class="clr-i-solid clr-i-solid-path-3 cxlln6pqv"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:lightbulb-solid" /></template>
