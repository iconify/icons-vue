<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vack09bmc.css';
import '../../css/z/zno_he9df.css';
import '../../css/m/mxe9l_zuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vack09bmc"/><path class="zno_he9df"/><path class="mxe9l_zuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:atom-bold-duotone" /></template>
