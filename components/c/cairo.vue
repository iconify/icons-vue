<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtgxhbc5g.css';
import '../../css/u/uidnkmboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vtgxhbc5g"/><path class="uidnkmboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cairo" /></template>
