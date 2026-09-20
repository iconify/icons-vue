<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jarezk6na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jarezk6na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-rounded-broken" /></template>
