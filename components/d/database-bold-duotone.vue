<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj705hhir.css';
import '../../css/i/ios08bb7p.css';
import '../../css/x/xi4-07bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj705hhir"/><path class="ios08bb7p"/><path class="xi4-07bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:database-bold-duotone" /></template>
