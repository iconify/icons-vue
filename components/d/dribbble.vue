<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr9x3pbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr9x3pbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dribbble" /></template>
