<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uok3q6dkc.css';
import '../../css/s/sf-d6_0vv.css';
import '../../css/g/gp5dk8tef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":365.56,"height":245.56,"left":-2.78,"top":54.22};
const content = `<path class="uok3q6dkc"/><path class="sf-d6_0vv"/><path class="gp5dk8tef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cloudevents" /></template>
