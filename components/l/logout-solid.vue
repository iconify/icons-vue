<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd8a_3tzp.css';
import '../../css/z/zv9pswjkm.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 vd8a_3tzp"/><path class="clr-i-solid clr-i-solid-path-2 zv9pswjkm"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:logout-solid" /></template>
