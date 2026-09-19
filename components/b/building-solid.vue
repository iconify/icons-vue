<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkk204bxw.css';
import '../../css/z/zzod9wung.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 xkk204bxw"/><path class="clr-i-solid clr-i-solid-path-2 zzod9wung"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:building-solid" /></template>
