<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzdv_ccir.css';
import '../../css/x/x9-rwuyde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="zzdv_ccir"/><path class="x9-rwuyde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-bold-duotone" /></template>
