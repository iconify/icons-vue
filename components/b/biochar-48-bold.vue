<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf3b3gb2z.css';
import '../../css/y/y9zlo3-ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wf3b3gb2z"/><path class="y9zlo3-ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biochar-48-bold" /></template>
