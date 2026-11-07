<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqfv9_bht.css';
import '../../css/g/g2z0o6bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqfv9_bht"/><path class="g2z0o6bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-from-line-bold-duotone" /></template>
