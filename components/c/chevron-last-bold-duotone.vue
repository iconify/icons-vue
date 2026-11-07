<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwow_w44a.css';
import '../../css/l/lsq66r8ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwow_w44a"/><path class="lsq66r8ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-last-bold-duotone" /></template>
