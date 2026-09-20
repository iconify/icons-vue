<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqbx_ob3b.css';
import '../../css/u/uxebd5iiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbx_ob3b"/><path class="uxebd5iiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:book" /></template>
