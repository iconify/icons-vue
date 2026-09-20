<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3q61blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw3q61blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:japanese-yen-duotone" /></template>
