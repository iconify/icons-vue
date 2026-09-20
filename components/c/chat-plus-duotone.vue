<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gojqxob8u.css';
import '../../css/s/sviu25l2e.css';
import '../../css/g/gcd2dxb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gojqxob8u"/><path class="sviu25l2e"/><path class="gcd2dxb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-plus-duotone" /></template>
