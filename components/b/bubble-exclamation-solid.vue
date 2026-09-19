<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8r8nxbmo.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b8r8nxbmo clr-i-solid clr-i-solid-path-1"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bubble-exclamation-solid" /></template>
