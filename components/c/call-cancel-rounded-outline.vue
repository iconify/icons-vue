<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi6_f9yez.css';
import '../../css/o/o4sar_bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi6_f9yez"/><path clip-rule="evenodd" class="o4sar_bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-cancel-rounded-outline" /></template>
