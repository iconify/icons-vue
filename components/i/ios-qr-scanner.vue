<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d145pkbyl.css';
import '../../css/u/u1jtw-d9c.css';
import '../../css/e/ejksmvbap.css';
import '../../css/s/shvrguwxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d145pkbyl"/><path class="u1jtw-d9c"/><path class="ejksmvbap"/><path class="shvrguwxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-qr-scanner" /></template>
