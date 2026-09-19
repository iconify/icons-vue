<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc_2rzbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rc_2rzbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:help-circle-solid" /></template>
