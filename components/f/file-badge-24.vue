<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec1mt9fwb.css';
import '../../css/h/h2sed2fvb.css';
import '../../css/n/nt1eozdqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1mt9fwb"/><path class="h2sed2fvb"/><path class="nt1eozdqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-badge-24" /></template>
