<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g89yo4bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g89yo4bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-centura" /></template>
