<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpaaegb5m.css';
import '../../css/q/qh8_e97db.css';
import '../../css/s/su66tdslr.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 lpaaegb5m"/><path class="clr-i-solid clr-i-solid-path-2 qh8_e97db"/><path class="clr-i-solid clr-i-solid-path-3 su66tdslr"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bitcoin-solid" /></template>
