<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4_kwrboz.css';
import '../../css/o/oa0cpabtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4_kwrboz"/><path class="oa0cpabtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-cloud" /></template>
