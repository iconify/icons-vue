<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hem1ktbzj.css';
import '../../css/v/v--qb2bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hem1ktbzj wm-k"/><path class="v--qb2bdl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:corner-down-right" /></template>
