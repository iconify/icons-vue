<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8b-p0atb.css';
import '../../css/r/rw8uhq80v.css';
import '../../css/f/f6u8m20fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8b-p0atb"/><path class="rw8uhq80v"/><path class="f6u8m20fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:boba" /></template>
