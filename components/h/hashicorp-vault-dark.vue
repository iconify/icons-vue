<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxpwfx6sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxpwfx6sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-vault-dark" /></template>
