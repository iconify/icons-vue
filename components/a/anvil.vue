<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n14bc-byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n14bc-byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:anvil" /></template>
