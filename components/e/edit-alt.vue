<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2h70hpmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2h70hpmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:edit-alt" /></template>
