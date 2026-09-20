<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lydqgnbpm.css';
import '../../css/a/a4bwvchjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lydqgnbpm"/><path class="a4bwvchjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:delta-air-lines" /></template>
