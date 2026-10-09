<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcwt57p0s.css';
import '../../css/x/xoykf8bsw.css';
import '../../css/q/qk7-h-neb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bcwt57p0s"/><path class="xoykf8bsw"/><path class="qk7-h-neb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-recycling-48" /></template>
