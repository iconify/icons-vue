<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw6ppgbbn.css';
import '../../css/w/wf_7x7bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw6ppgbbn"/><path class="wf_7x7bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-typescript" /></template>
