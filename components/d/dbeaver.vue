<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixspvj17v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixspvj17v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dbeaver" /></template>
