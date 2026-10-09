<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayan5y9nl.css';
import '../../css/q/qhc6f6b0w.css';
import '../../css/i/inu9gabyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ayan5y9nl"/><path class="qhc6f6b0w"/><path class="inu9gabyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:engineer-48-bold" /></template>
