<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_x9xmbd.css';
import '../../css/c/c-ivyjb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_x9xmbd"/><path class="c-ivyjb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-right-bold-duotone" /></template>
