<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whw3bdb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whw3bdb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flower-sharp-duotone" /></template>
