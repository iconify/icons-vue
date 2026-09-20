<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3r4zzb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3r4zzb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dollar-duotone" /></template>
