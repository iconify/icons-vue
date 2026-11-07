<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omll7putu.css';
import '../../css/b/bidhrk63b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omll7putu"/><path class="bidhrk63b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-to-line-bold-duotone" /></template>
