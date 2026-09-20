<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqc5dho9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wqc5dho9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-vault-light" /></template>
