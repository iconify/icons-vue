<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvs6jjb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvs6jjb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:claude" /></template>
