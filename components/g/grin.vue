<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lntkcpb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lntkcpb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:grin" /></template>
