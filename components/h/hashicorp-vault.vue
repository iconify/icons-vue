<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xip5n6bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xip5n6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-vault" /></template>
