<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-oypdbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-oypdbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-bolt" /></template>
