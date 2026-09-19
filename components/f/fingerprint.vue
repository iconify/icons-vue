<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_s-s2rgw.css';
import '../../css/t/te525ybvr.css';
import '../../css/i/ih6yu9j5y.css';
import '../../css/t/tnnhe8b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_s-s2rgw"/><path class="te525ybvr"/><path class="ih6yu9j5y"/><path class="tnnhe8b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:fingerprint" /></template>
