<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqovhacve.css';
import '../../css/g/gt43axbik.css';
import '../../css/d/dlr77pb9n.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 pqovhacve"/><path class="clr-i-outline clr-i-outline-path-2 gt43axbik"/><path class="clr-i-outline clr-i-outline-path-3 dlr77pb9n"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:clone-line" /></template>
