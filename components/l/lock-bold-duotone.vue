<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dnrk_0v.css';
import '../../css/y/ywc-2eb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dnrk_0v"/><path class="ywc-2eb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-bold-duotone" /></template>
