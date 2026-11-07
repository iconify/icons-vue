<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo0xsojdd.css';
import '../../css/o/o4sar_bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo0xsojdd"/><path clip-rule="evenodd" class="o4sar_bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-dropped-rounded-outline" /></template>
