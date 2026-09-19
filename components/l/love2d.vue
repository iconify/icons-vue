<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxvv67rcf.css';
import '../../css/g/glsd4_26w.css';
import '../../css/i/ifus-gbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hxvv67rcf"/><path class="glsd4_26w"/><path class="ifus-gbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:love2d" /></template>
