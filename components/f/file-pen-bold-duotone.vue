<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgissgbda.css';
import '../../css/t/t3fbyzb7o.css';
import '../../css/o/ont9fsbmp.css';
import '../../css/h/hvizvfbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgissgbda"/><path class="t3fbyzb7o"/><path class="ont9fsbmp"/><path class="hvizvfbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-pen-bold-duotone" /></template>
