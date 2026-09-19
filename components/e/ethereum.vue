<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkftwccsp.css';
import '../../css/b/bvk3h70eg.css';
import '../../css/g/gjx8-pb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="vkftwccsp"/><path class="bvk3h70eg"/><path class="gjx8-pb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:ethereum" /></template>
