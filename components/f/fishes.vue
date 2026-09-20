<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmmcl_mnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmmcl_mnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:fishes" /></template>
