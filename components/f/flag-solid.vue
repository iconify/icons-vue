<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xulwhlnvn.css';
import '../../css/i/ig66h0gfs.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 xulwhlnvn"/><path class="clr-i-solid clr-i-solid-path-2 ig66h0gfs"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:flag-solid" /></template>
