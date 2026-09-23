<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as0oiybee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as0oiybee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-down-right-sharp-duotone" /></template>
