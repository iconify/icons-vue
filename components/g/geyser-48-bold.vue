<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6cvwtbsp.css';
import '../../css/e/eh_8zfvcn.css';
import '../../css/r/rmyb_66he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="eh_8zfvcn"/><path class="rmyb_66he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geyser-48-bold" /></template>
