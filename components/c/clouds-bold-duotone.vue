<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czdsxrb2c.css';
import '../../css/e/ewaos-x_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czdsxrb2c"/><path class="ewaos-x_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clouds-bold-duotone" /></template>
