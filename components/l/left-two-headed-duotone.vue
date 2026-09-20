<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng2ie-b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2ie-b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-two-headed-duotone" /></template>
