<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orp_ksb2f.css';
import '../../css/b/bt4q5sbjw.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 orp_ksb2f"/><path class="bt4q5sbjw clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:disconnect-solid" /></template>
