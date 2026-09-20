<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz3d-2pmb.css';
import '../../css/s/spm3uswvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz3d-2pmb"/><path class="spm3uswvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:edit" /></template>
