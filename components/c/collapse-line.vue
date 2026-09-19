<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adj9vabdu.css';
import '../../css/i/ijbujlbwg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="adj9vabdu clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 ijbujlbwg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:collapse-line" /></template>
