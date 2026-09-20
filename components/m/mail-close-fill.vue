<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urr3lhbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urr3lhbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-close-fill" /></template>
