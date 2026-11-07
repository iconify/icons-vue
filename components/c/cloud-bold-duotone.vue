<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk87vthwz.css';
import '../../css/v/v7o6jqpbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gk87vthwz"/><path class="v7o6jqpbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-bold-duotone" /></template>
