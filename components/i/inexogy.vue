<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahba87blp.css';
import '../../css/v/vmcevybnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahba87blp"/><path class="vmcevybnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inexogy" /></template>
