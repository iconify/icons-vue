<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjd2j9mqk.css';
import '../../css/m/mfah0lbew.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 yjd2j9mqk"/><path class="clr-i-solid clr-i-solid-path-1 mfah0lbew"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:filter-solid" /></template>
