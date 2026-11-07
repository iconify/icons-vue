<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1ndrfb_z.css';
import '../../css/x/x4f46-b2l.css';
import '../../css/a/ayfii2kus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ndrfb_z"/><path class="x4f46-b2l"/><path class="ayfii2kus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-corrupted-bold-duotone" /></template>
