<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3nd6zn0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3nd6zn0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad" /></template>
