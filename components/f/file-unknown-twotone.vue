<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1h2ywb3p.css';
import '../../css/z/z4pv5t1oe.css';
import '../../css/u/ub1afpn4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r1h2ywb3p"/><path class="z4pv5t1oe"/><path class="ub1afpn4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-unknown-twotone" /></template>
