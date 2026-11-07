<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud3fqxmls.css';
import '../../css/b/bdo_xv7jy.css';
import '../../css/q/q0ro-4hck.css';
import '../../css/c/cr29i4b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ud3fqxmls"/><path class="bdo_xv7jy"/><path class="q0ro-4hck"/><path class="cr29i4b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-rain-bold" /></template>
