<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqyoi2ukf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqyoi2ukf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-wall-nyro-flood" /></template>
