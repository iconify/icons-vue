<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyjanl8xm.css';
import '../../css/l/l-7l4bc0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyjanl8xm"/><path class="l-7l4bc0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-bold-duotone" /></template>
