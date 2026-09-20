<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shdyh8bir.css';
import '../../css/a/ay_63acmb.css';
import '../../css/d/dyv9fpbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shdyh8bir"/><path class="ay_63acmb"/><path class="dyv9fpbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:langflow" /></template>
