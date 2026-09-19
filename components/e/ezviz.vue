<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7a0u441t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7a0u441t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ezviz" /></template>
