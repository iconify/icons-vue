<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh9q8b7lx.css';
import '../../css/g/gtdmtvp5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh9q8b7lx"/><path class="gtdmtvp5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:copy-outline" /></template>
