<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upcj_ab3a.css';
import '../../css/u/ui4msccxe.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 upcj_ab3a"/><path class="clr-i-outline clr-i-outline-path-2 ui4msccxe"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:file-share-line" /></template>
