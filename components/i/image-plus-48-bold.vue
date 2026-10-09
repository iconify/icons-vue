<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggjbj35_l.css';
import '../../css/z/zy7ka5dsb.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ggjbj35_l"/><path class="zy7ka5dsb"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-plus-48-bold" /></template>
