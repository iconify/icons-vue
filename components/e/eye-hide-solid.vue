<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izt-xbfer.css';
import '../../css/b/buyojelvy.css';
import '../../css/q/qk1bvjeqe.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 izt-xbfer"/><path class="buyojelvy clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 qk1bvjeqe"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:eye-hide-solid" /></template>
