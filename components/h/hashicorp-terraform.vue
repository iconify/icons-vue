<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw1vftp4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gw1vftp4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-terraform" /></template>
