<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6fqpguta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6fqpguta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-terraform-light" /></template>
