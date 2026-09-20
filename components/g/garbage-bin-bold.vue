<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssv2r9bnu.css';
import '../../css/o/o2pei4b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssv2r9bnu"/><path class="o2pei4b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:garbage-bin-bold" /></template>
